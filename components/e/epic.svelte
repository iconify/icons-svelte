<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwc2g5b2a.css';
import '../../css/p/pjb5o-bcb.css';
import '../../css/q/qapg4nbep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nwc2g5b2a"/><path class="pjb5o-bcb"/><path clip-rule="evenodd" class="qapg4nbep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:epic" {...props}></Icon>
