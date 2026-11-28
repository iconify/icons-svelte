<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2b7ppscw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary u2b7ppscw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:lungs-duotone" {...props}></Icon>
