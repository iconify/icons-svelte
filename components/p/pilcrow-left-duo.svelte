<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5sle4ebl.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/a/ap3wsxbft.css';
import '../../css/m/m_kz9zbhm.css';
import '../../css/m/mh6khlbtv.css';
import '../../css/s/s2mq98boy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s5sle4ebl secondary"/><g class="dt0cm9dhy primary"><path class="ap3wsxbft"/><path class="m_kz9zbhm"/><path class="mh6khlbtv"/><path class="s2mq98boy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pilcrow-left-duo" {...props}></Icon>
