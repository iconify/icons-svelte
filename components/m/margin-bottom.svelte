<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w40h5abuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w40h5abuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:margin-bottom" {...props}></Icon>
