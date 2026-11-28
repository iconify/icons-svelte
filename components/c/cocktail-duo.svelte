<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gl4kkzb5g.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/i8wtt5bzu.css';
import '../../css/i/i_c4vbt4x.css';
import '../../css/l/lb_6x_9bo.css';
import '../../css/f/fn0m0tdnr.css';
import '../../css/j/jwjkiwb3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gl4kkzb5g secondary"/><g class="dt0cm9dhy primary"><path class="i8wtt5bzu"/><path class="i_c4vbt4x"/><path class="lb_6x_9bo"/><path class="fn0m0tdnr"/><path class="jwjkiwb3k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cocktail-duo" {...props}></Icon>
