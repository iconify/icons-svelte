<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbhchdb7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jbhchdb7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:bitcoin" {...props}></Icon>
