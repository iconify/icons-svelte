<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u676mrb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u676mrb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:confetti" {...props}></Icon>
