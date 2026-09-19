<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-e-5bb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-e-5bb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:crown" {...props}></Icon>
