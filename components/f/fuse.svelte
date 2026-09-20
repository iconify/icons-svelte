<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmafcacme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmafcacme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:fuse" {...props}></Icon>
