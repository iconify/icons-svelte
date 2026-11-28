<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3oq4jbwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h3oq4jbwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:play-circle-solid" {...props}></Icon>
