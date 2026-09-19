<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lw63rpeky.css';
import '../../css/m/mfbf4utcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lw63rpeky"/><path class="mfbf4utcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:forum" {...props}></Icon>
