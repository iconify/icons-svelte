<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odsay3b2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="odsay3b2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:checkboxes-blank-circle-outline" {...props}></Icon>
