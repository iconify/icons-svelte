<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3uu5lbtk.css';
import '../../css/o/omkgw9bsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s3uu5lbtk"/><path class="omkgw9bsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:alien" {...props}></Icon>
