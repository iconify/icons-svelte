<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qe894tblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qe894tblh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:arrow-align-v" {...props}></Icon>
