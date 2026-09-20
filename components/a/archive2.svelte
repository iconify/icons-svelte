<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smyzkjknw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="smyzkjknw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:archive2" {...props}></Icon>
