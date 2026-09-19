<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1b5yub_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j1b5yub_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:paved-road-24px" {...props}></Icon>
