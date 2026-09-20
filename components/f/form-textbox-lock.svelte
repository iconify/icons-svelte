<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrsp6jjiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nrsp6jjiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:form-textbox-lock" {...props}></Icon>
