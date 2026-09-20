<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmm71acjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hmm71acjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:dumbbell" {...props}></Icon>
