<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yloeidcsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yloeidcsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:disable-protection" {...props}></Icon>
