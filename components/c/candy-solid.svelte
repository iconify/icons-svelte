<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fphb3weuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fphb3weuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:candy-solid" {...props}></Icon>
