<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5kjy4_hr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o5kjy4_hr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:kusto" {...props}></Icon>
