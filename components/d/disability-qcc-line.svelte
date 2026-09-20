<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it_ryvbvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="it_ryvbvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:disability-qcc-line" {...props}></Icon>
