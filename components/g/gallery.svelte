<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mb40d305w.css';
import '../../css/y/y850ku1de.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="mb40d305w"/><path class="y850ku1de"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:gallery" {...props}></Icon>
