<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qan-v46oz.css';
import '../../css/r/r-dqwzb9h.css';
import '../../css/s/s2i58ab4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qan-v46oz"/><path class="r-dqwzb9h"/><path class="s2i58ab4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloche-20" {...props}></Icon>
