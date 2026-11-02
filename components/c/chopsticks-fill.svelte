<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtb85pbou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mtb85pbou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chopsticks-fill" {...props}></Icon>
