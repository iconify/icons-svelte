<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od73h5bsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="od73h5bsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:phone" {...props}></Icon>
