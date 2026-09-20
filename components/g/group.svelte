<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9mbmacac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="t9mbmacac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:group" {...props}></Icon>
