<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugj8ebreh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary ugj8ebreh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:barcode-duotone" {...props}></Icon>
