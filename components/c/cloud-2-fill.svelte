<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m35kljbyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m35kljbyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cloud-2-fill" {...props}></Icon>
