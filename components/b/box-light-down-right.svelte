<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihsfb_26y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ihsfb_26y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-down-right" {...props}></Icon>
