<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc6xorb6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xc6xorb6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-backspace" {...props}></Icon>
