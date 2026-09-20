<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c810rab6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c810rab6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clock-6" {...props}></Icon>
