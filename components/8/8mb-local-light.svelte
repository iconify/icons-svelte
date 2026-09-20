<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcpc8aclj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tcpc8aclj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:8mb-local-light" {...props}></Icon>
