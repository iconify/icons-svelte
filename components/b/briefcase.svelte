<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnohpmb3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qnohpmb3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:briefcase" {...props}></Icon>
