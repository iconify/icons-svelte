<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hamm36bqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hamm36bqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-phone-portrait" {...props}></Icon>
