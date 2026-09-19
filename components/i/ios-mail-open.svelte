<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znuap0b9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="znuap0b9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-mail-open" {...props}></Icon>
