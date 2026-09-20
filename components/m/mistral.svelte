<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m96o_vbpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m96o_vbpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:mistral" {...props}></Icon>
