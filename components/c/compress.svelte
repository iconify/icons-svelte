<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay6-rac8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ay6-rac8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:compress" {...props}></Icon>
