<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z14bdvjpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z14bdvjpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:package-dimension-bold" {...props}></Icon>
