<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txvldt9ed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="txvldt9ed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-unlock" {...props}></Icon>
