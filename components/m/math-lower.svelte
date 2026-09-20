<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eme4g79qd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eme4g79qd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:math-lower" {...props}></Icon>
