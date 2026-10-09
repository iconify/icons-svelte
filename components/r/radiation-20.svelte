<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2-3n8bey.css';
import '../../css/q/q7a8l0b_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a2-3n8bey"/><path class="q7a8l0b_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:radiation-20" {...props}></Icon>
