<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/za_zbub4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="za_zbub4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:bolt-badge-a" {...props}></Icon>
