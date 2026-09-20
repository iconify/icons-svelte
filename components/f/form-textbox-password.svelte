<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oryz2vb-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oryz2vb-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:form-textbox-password" {...props}></Icon>
