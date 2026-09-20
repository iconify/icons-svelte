<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_n7pbc6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m_n7pbc6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cilium-tetragon-light" {...props}></Icon>
