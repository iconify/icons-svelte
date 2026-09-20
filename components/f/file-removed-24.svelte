<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-szn7-xv.css';
import '../../css/q/qtp0labzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-szn7-xv"/><path class="qtp0labzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:file-removed-24" {...props}></Icon>
