<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/p/pl2kf0_ch.css';
import '../../css/w/w65t7vpsn.css';
import '../../css/d/dos_yhbgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pl2kf0_ch"/><circle class="w65t7vpsn"/><circle class="dos_yhbgg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:git-branch-minus" {...props}></Icon>
