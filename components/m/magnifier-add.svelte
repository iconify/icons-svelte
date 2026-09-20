<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfoah-o_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xfoah-o_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:magnifier-add" {...props}></Icon>
