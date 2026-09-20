<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hoqqhpbnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hoqqhpbnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:key-alert-outline" {...props}></Icon>
