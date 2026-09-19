<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvi6kbbfc.css';
import '../../css/a/aueya6btf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pvi6kbbfc"/><path class="aueya6btf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:link-external" {...props}></Icon>
