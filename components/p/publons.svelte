<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exwyr5jvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="exwyr5jvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:publons" {...props}></Icon>
