<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcfaj0bdj.css';
import '../../css/c/c7b0ob2tk.css';
import '../../css/r/rcidtuiap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcfaj0bdj"/><path class="c7b0ob2tk"/><path class="rcidtuiap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:dashboard-duotone" {...props}></Icon>
