<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tu6plhk2a.css';
import '../../css/m/mb34tibqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tu6plhk2a"/><path class="mb34tibqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:logo-social-media-twitter-circle" {...props}></Icon>
