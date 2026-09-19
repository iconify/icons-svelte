<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzibc2lul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qzibc2lul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:calendar2-check-fill" {...props}></Icon>
