<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ous1cc4fm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ous1cc4fm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:paved-road-alt-outline-24px" {...props}></Icon>
