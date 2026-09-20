<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ed_ztubpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ed_ztubpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:chevron-right-alt-duotone" {...props}></Icon>
