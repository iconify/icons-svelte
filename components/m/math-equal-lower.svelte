<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guiyaubla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="guiyaubla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:math-equal-lower" {...props}></Icon>
