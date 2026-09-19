<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3kne6g0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f3kne6g0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:no-symbol-solid" {...props}></Icon>
