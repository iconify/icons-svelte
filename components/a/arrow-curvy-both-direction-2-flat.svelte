<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxgi8ob_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="wxgi8ob_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:arrow-curvy-both-direction-2-flat" {...props}></Icon>
