<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kq-l14o0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="kq-l14o0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:cloud" {...props}></Icon>
