<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk3didcla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dk3didcla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:lifebuoy-fill" {...props}></Icon>
