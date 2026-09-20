<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4mnracmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b4mnracmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:hand-mic" {...props}></Icon>
