<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz7spkb-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="zz7spkb-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:rain" {...props}></Icon>
