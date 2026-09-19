<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yil8a7ebz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yil8a7ebz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:chevron-forward-sharp" {...props}></Icon>
