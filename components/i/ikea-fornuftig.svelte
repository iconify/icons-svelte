<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0-1bibag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p0-1bibag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ikea-fornuftig" {...props}></Icon>
