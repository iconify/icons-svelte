<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvnx57abk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hvnx57abk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:invoice-edit-outline" {...props}></Icon>
