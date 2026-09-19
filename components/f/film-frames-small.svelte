<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lj-iyog-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="lj-iyog-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:film-frames-small" {...props}></Icon>
