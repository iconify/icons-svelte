<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0_zj3bxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="l0_zj3bxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:cut" {...props}></Icon>
