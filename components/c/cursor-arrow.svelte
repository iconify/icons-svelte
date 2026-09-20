<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyd-i4gvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nyd-i4gvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:cursor-arrow" {...props}></Icon>
