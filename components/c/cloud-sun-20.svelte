<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9w0q_b5k.css';
import '../../css/n/nc1vrqo3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p9w0q_b5k"/><path class="nc1vrqo3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-sun-20" {...props}></Icon>
