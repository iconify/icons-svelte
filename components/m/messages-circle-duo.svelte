<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rcu59kbfz.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/c/c0mmavm7v.css';
import '../../css/e/e8wttxgta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rcu59kbfz secondary"/><g class="dt0cm9dhy primary"><path class="c0mmavm7v"/><path class="e8wttxgta"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:messages-circle-duo" {...props}></Icon>
