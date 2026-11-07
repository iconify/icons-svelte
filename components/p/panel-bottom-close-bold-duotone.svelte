<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nq9rqn1zt.css';
import '../../css/w/wj_8rllsk.css';
import '../../css/n/na-mcbnwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nq9rqn1zt"/><path class="wj_8rllsk"/><path class="na-mcbnwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panel-bottom-close-bold-duotone" {...props}></Icon>
