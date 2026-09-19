<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gobf57txj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gobf57txj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:cross" {...props}></Icon>
