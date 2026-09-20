<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vo6ln3mqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":16};
const content = `<path class="vo6ln3mqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:grabber" {...props}></Icon>
