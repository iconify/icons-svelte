<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7vaxix2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x7vaxix2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:bell-slash-24" {...props}></Icon>
