<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lboj9uczw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lboj9uczw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:radio-button" {...props}></Icon>
