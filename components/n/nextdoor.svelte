<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh_2ys6yn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gh_2ys6yn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:nextdoor" {...props}></Icon>
