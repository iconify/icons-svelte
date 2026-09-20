<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8z54chjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n8z54chjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:inertia" {...props}></Icon>
