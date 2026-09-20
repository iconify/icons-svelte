<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njc6ft7np.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njc6ft7np"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:chart-covariate" {...props}></Icon>
