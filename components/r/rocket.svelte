<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd6s21l_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zd6s21l_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:rocket" {...props}></Icon>
