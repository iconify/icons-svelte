<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/juf74mb5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="juf74mb5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:other-ui-send" {...props}></Icon>
