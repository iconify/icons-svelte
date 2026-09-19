<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojnmpz68t.css';
import '../../css/j/jsoljj9wy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ojnmpz68t"/><path class="jsoljj9wy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:guitar-amp" {...props}></Icon>
