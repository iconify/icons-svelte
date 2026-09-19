<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8efn-fzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":960};
const content = `<path class="h8efn-fzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:event" {...props}></Icon>
