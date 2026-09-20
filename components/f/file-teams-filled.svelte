<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_lieacpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_lieacpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:file-teams-filled" {...props}></Icon>
