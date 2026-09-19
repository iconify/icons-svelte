<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnl7bw4sb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mnl7bw4sb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:lark" {...props}></Icon>
