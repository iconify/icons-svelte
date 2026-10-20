<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex7-f_rng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ex7-f_rng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:chart-no-axes-column" {...props}></Icon>
