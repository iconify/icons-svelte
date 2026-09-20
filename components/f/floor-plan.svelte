<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1n9hbhdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n1n9hbhdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:floor-plan" {...props}></Icon>
