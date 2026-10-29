<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/eznyqtlvj.css';
import '../../css/n/nymx0iq8a.css';
import '../../css/z/zp22uibdm.css';
import '../../css/l/l_3wwtr4y.css';
import '../../css/x/xd03305qw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="eznyqtlvj wm-k"/><path class="nymx0iq8a wm-k"/><path class="wm-a zp22uibdm"/><path class="l_3wwtr4y wm-s"/><path class="wm-s xd03305qw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bell-off-sketch" {...props}></Icon>
