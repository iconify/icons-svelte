<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh7jq3fss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="yh7jq3fss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:postcss" {...props}></Icon>
