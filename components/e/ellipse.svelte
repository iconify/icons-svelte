<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcwutrxfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<ellipse class="kcwutrxfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ellipse" {...props}></Icon>
