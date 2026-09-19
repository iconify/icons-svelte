<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5tmslb6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q5tmslb6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:dashboard-circle" {...props}></Icon>
