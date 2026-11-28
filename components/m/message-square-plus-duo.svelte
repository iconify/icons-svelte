<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjd2x0bfl.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/dp12a2bii.css';
import '../../css/m/m4818gzkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjd2x0bfl secondary"/><g class="dt0cm9dhy primary"><path class="dp12a2bii"/><path class="m4818gzkb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-square-plus-duo" {...props}></Icon>
