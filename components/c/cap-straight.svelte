<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/v/v_mf6nbvh.css';
import '../../css/y/ybsqlk_rx.css';
import '../../css/v/vdc6itbws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="v_mf6nbvh"/><path class="ybsqlk_rx"/><path class="vdc6itbws"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cap-straight" {...props}></Icon>
