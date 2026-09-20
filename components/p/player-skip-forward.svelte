<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/giu7wm7zs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="giu7wm7zs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:player-skip-forward" {...props}></Icon>
