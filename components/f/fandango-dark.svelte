<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcmf__n-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vcmf__n-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fandango-dark" {...props}></Icon>
