<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbsrd8h1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rbsrd8h1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ara-records-ansible-dark" {...props}></Icon>
