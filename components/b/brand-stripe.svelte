<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtv_b7_ax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qtv_b7_ax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-stripe" {...props}></Icon>
