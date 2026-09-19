<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elcz3zykd.css';
import '../../css/q/q_tt9nb9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer elcz3zykd"/><path class="duoicon-primary-layer q_tt9nb9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:coin-stack" {...props}></Icon>
