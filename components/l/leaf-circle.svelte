<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7qddtfde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7qddtfde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:leaf-circle" {...props}></Icon>
