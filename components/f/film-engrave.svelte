<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/bokapyb6e.css';
import '../../css/f/f93v21bsx.css';
import '../../css/f/fv6kukroi.css';
import '../../css/e/euj49csjz.css';
import '../../css/m/my7poevrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="bokapyb6e wm-k"/><path class="f93v21bsx wm-a"/><path class="fv6kukroi wm-shadow"/><path class="euj49csjz wm-k"/><path class="my7poevrw wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:film-engrave" {...props}></Icon>
