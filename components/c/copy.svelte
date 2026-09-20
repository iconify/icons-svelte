<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbg7job8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pbg7job8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:copy" {...props}></Icon>
