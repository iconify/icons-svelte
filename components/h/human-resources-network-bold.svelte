<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdjwxdbku.css';
import '../../css/b/bpczg_bnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gdjwxdbku"/><path class="bpczg_bnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:human-resources-network-bold" {...props}></Icon>
