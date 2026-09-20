<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/impn5pp0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="impn5pp0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:mood-frown-solid" {...props}></Icon>
