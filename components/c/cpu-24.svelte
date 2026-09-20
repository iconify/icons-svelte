<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2cwfz8jg.css';
import '../../css/s/s5kpojbcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o2cwfz8jg"/><path class="s5kpojbcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:cpu-24" {...props}></Icon>
