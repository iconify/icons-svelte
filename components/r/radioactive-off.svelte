<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbi5g97mr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hbi5g97mr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:radioactive-off" {...props}></Icon>
