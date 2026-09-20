<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz41yccml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oz41yccml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:desk-lamp" {...props}></Icon>
