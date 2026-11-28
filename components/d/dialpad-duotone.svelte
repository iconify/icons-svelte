<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m942_cbxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m942_cbxv primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:dialpad-duotone" {...props}></Icon>
