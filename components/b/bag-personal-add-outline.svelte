<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/baqfxqy0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="baqfxqy0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bag-personal-add-outline" {...props}></Icon>
