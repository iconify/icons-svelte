<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oof_vgboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oof_vgboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:nex" {...props}></Icon>
