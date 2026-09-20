<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/levk4gbjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="levk4gbjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:dashboard-circle-bar-fill" {...props}></Icon>
