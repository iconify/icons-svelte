<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/teymdtb4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="teymdtb4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:cornet" {...props}></Icon>
