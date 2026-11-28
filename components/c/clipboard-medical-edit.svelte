<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgnvt6b9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sgnvt6b9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:clipboard-medical-edit" {...props}></Icon>
