<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1-iiebzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="t1-iiebzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:online" {...props}></Icon>
