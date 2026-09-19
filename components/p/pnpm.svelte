<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd2ys0b6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vd2ys0b6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:pnpm" {...props}></Icon>
