<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwb9z7q9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pwb9z7q9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:hourglass" {...props}></Icon>
