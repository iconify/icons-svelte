<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbgxfd0gy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sbgxfd0gy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:mail" {...props}></Icon>
