<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ka7_x7bmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ka7_x7bmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:projector-line" {...props}></Icon>
