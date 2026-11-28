<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es0p8gbiv.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/r/rrq4fhbji.css';
import '../../css/v/vik7aybod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="es0p8gbiv secondary"/><g class="dt0cm9dhy primary"><path class="rrq4fhbji"/><path class="vik7aybod"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cloud-rain-heavy-duo" {...props}></Icon>
