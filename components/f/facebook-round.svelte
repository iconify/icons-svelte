<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1szsdb8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z1szsdb8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:facebook-round" {...props}></Icon>
