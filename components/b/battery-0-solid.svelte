<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5l_d69-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o5l_d69-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:battery-0-solid" {...props}></Icon>
