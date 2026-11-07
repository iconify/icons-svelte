<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rj_kwrbir.css';
import '../../css/j/jaafzgbna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rj_kwrbir"/><path class="jaafzgbna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dumbbells-bold" {...props}></Icon>
