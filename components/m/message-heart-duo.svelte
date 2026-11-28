<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oecy3qhop.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/gtipehbld.css';
import '../../css/w/wpsx3fbcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oecy3qhop secondary"/><g class="dt0cm9dhy primary"><path class="gtipehbld"/><path class="wpsx3fbcj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-heart-duo" {...props}></Icon>
