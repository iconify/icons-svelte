<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgq-79blj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rgq-79blj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:cat-big" {...props}></Icon>
