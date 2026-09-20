<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwh7egbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mwh7egbqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:dumbbell" {...props}></Icon>
