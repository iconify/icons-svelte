<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukba4dbai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ukba4dbai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:pie-chart" {...props}></Icon>
