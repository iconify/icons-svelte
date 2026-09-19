<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pou4mbcvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pou4mbcvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:pentagon-top-right" {...props}></Icon>
