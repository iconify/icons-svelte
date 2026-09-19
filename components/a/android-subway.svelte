<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxx8ae6fm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vxx8ae6fm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-subway" {...props}></Icon>
