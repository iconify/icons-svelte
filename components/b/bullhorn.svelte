<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf41albxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nf41albxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:bullhorn" {...props}></Icon>
