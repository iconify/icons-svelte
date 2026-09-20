<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckq3cfb9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ckq3cfb9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:nhl" {...props}></Icon>
