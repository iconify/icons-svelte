<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eh6xlccjr.css';
import '../../css/o/o-szn7-xv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eh6xlccjr"/><path class="o-szn7-xv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:file-added-24" {...props}></Icon>
