<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yukx63bct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="yukx63bct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:balloon-solid" {...props}></Icon>
