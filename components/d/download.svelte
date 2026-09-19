<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psv6wg5ow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="psv6wg5ow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:download" {...props}></Icon>
