<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wo0c38buo.css';
import '../../css/c/ciwabiowf.css';
import '../../css/d/diidstw8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wo0c38buo"/><path clip-rule="evenodd" class="ciwabiowf"/><path class="diidstw8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:galaxy-filled" {...props}></Icon>
