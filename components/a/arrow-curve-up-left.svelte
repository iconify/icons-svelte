<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr8dwupne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cr8dwupne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-curve-up-left" {...props}></Icon>
