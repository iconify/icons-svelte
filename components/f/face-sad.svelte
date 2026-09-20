<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fndgsfbhl.css';
import '../../css/o/ooafjrbnh.css';
import '../../css/v/vd27ehbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fndgsfbhl"/><path class="ooafjrbnh"/><path class="vd27ehbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:face-sad" {...props}></Icon>
