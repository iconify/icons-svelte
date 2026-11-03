<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7rvicsjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e7rvicsjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:bluetooth" {...props}></Icon>
