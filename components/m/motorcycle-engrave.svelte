<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/fqlbot_9u.css';
import '../../css/u/utsgd96vm.css';
import '../../css/r/rlrgvvbrl.css';
import '../../css/s/spev02xtm.css';
import '../../css/q/qw3cslx4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="fqlbot_9u wm-k"/><path class="utsgd96vm wm-a"/><path class="rlrgvvbrl wm-shadow"/><path class="spev02xtm wm-k"/><path class="qw3cslx4k wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:motorcycle-engrave" {...props}></Icon>
