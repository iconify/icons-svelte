<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjd2x0bfl.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/dp12a2bii.css';
import '../../css/n/n5y6r804h.css';
import '../../css/t/tocyj6bym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjd2x0bfl secondary"/><g class="dt0cm9dhy primary"><path class="dp12a2bii"/><path class="n5y6r804h"/><path class="tocyj6bym"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-square-diff-duo" {...props}></Icon>
