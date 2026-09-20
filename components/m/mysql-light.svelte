<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w84gw5bsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w84gw5bsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mysql-light" {...props}></Icon>
