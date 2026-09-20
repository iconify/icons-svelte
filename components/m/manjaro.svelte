<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7ezm804z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l7ezm804z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:manjaro" {...props}></Icon>
