<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc1xdqzrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xc1xdqzrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:application-add" {...props}></Icon>
