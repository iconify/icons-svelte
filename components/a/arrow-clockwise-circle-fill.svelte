<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hotf6gb9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="hotf6gb9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-clockwise-circle-fill" {...props}></Icon>
