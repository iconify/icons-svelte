<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4lq4-bat.css';
import '../../css/q/qv1r8v-de.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g4lq4-bat"/><path class="qv1r8v-de"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:euro-20" {...props}></Icon>
