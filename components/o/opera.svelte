<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5eussbda.css';
import '../../css/e/e6n3rcb6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q5eussbda"/><path class="e6n3rcb6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:opera" {...props}></Icon>
