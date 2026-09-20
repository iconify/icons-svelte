<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-sxvv4kb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-sxvv4kb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:body-linear" {...props}></Icon>
