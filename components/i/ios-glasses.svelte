<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwm7qldww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xwm7qldww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-glasses" {...props}></Icon>
