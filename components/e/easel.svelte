<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad1eawq9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ad1eawq9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:easel" {...props}></Icon>
