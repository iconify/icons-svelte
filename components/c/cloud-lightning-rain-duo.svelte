<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm6y7qboy.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/txf_xf5pi.css';
import '../../css/m/myy3teiet.css';
import '../../css/w/wpnykd7ac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cm6y7qboy secondary"/><g class="dt0cm9dhy primary"><path class="txf_xf5pi"/><path class="myy3teiet"/><path class="wpnykd7ac"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cloud-lightning-rain-duo" {...props}></Icon>
