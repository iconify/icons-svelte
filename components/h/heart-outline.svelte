<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9rzljb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w9rzljb1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:heart-outline" {...props}></Icon>
