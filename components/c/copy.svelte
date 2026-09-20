<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5ebiebcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5ebiebcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:copy" {...props}></Icon>
