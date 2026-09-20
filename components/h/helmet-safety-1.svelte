<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p97i2jbqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="p97i2jbqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:helmet-safety-1" {...props}></Icon>
