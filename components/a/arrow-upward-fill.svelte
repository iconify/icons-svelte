<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/engovybkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="engovybkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:arrow-upward-fill" {...props}></Icon>
