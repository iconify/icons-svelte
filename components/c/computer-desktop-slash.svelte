<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufmuf6t2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufmuf6t2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:computer-desktop-slash" {...props}></Icon>
