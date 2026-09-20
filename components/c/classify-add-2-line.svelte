<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amf1k8b6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="amf1k8b6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:classify-add-2-line" {...props}></Icon>
