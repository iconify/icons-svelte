<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3nbq0pup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1504};
const content = `<path class="u3nbq0pup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:commenting" {...props}></Icon>
