<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtcuhubrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jtcuhubrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:horizontal-rule-24" {...props}></Icon>
