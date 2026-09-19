<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkc3rh37p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":448};
const content = `<path class="wkc3rh37p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:photobucket" {...props}></Icon>
