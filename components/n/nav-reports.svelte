<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkrjhob6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tkrjhob6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:nav-reports" {...props}></Icon>
