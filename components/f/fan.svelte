<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzy6kp86h.css';
import '../../css/k/k70t2o__t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzy6kp86h"/><path class="k70t2o__t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:fan" {...props}></Icon>
