<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5tcmf-xm.css';
import '../../css/w/wo40o9c3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f5tcmf-xm"/><path class="wo40o9c3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:init-container" {...props}></Icon>
