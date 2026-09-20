<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvvm0fb4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pvvm0fb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hubzilla-dark" {...props}></Icon>
