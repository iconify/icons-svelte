<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzx4-eb4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="zzx4-eb4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:clipboard" {...props}></Icon>
