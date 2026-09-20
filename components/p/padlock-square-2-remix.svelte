<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pem9t_bvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="pem9t_bvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:padlock-square-2-remix" {...props}></Icon>
