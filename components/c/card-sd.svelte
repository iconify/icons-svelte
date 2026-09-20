<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb8i3i-kg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qb8i3i-kg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:card-sd" {...props}></Icon>
