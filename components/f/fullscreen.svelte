<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or_nacp9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="or_nacp9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:fullscreen" {...props}></Icon>
