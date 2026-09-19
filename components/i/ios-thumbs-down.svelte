<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpw57j1qs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hpw57j1qs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-thumbs-down" {...props}></Icon>
