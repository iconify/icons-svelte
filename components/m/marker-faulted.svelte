<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qthlpib6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qthlpib6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="evicons:marker-faulted" {...props}></Icon>
