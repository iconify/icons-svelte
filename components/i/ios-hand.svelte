<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz6ec88-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zz6ec88-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-hand" {...props}></Icon>
