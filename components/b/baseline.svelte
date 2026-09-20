<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_fti0d4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t_fti0d4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:baseline" {...props}></Icon>
