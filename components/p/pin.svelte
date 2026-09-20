<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a21x_b8wq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="a21x_b8wq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:pin" {...props}></Icon>
