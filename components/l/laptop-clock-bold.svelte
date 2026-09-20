<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-vp84b5b.css';
import '../../css/j/jkrx8ppgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-vp84b5b"/><path class="jkrx8ppgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:laptop-clock-bold" {...props}></Icon>
