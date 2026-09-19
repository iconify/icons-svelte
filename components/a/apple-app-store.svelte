<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro7ekkbkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ro7ekkbkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:apple-app-store" {...props}></Icon>
