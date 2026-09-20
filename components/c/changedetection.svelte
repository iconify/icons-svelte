<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5su30b5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u5su30b5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:changedetection" {...props}></Icon>
