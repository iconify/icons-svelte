<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or2oxoa9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="or2oxoa9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:heliport" {...props}></Icon>
