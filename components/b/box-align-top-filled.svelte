<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/daaah39dx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="daaah39dx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:box-align-top-filled" {...props}></Icon>
