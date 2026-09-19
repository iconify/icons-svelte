<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5alf1blp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="f5alf1blp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:bringtofront" {...props}></Icon>
