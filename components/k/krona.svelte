<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d47xi2b9o.css';
import '../../css/f/fjryjwbdx.css';
import '../../css/n/nydaq4aap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d47xi2b9o"/><path class="fjryjwbdx"/><path class="nydaq4aap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:krona" {...props}></Icon>
