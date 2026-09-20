<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_y028i5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="c_y028i5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:ask-question" {...props}></Icon>
