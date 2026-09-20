<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyustebbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oyustebbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:globe-cursor-fill" {...props}></Icon>
