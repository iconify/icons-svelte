<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqsrefbbc.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/vtpmdroha.css';
import '../../css/e/e_0oumv9u.css';
import '../../css/q/qmqxyprqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqsrefbbc secondary"/><g class="dt0cm9dhy primary"><path class="vtpmdroha"/><path class="e_0oumv9u"/><path class="qmqxyprqi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:hammer-duo" {...props}></Icon>
