<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-i491roh.css';
import '../../css/a/amho5bkqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-i491roh wm-k"/><path class="amho5bkqy wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:redo" {...props}></Icon>
