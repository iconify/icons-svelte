<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/d/d67uiab3g.css';
import '../../css/h/hbsfdvpyk.css';
import '../../css/h/htrp6gb9i.css';
import '../../css/g/guehvl8mh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d67uiab3g"/><path class="hbsfdvpyk"/><path class="htrp6gb9i"/><path class="guehvl8mh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:book-open-bookmark" {...props}></Icon>
