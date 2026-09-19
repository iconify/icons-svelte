<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok8u8ubdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ok8u8ubdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:admin-plugins" {...props}></Icon>
