<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ch77nccom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ch77nccom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:globe-alt-2" {...props}></Icon>
