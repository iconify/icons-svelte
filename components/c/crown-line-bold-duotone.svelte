<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zq8bxxi9p.css';
import '../../css/z/zyfh3yufc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zq8bxxi9p"/><path class="zyfh3yufc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:crown-line-bold-duotone" {...props}></Icon>
