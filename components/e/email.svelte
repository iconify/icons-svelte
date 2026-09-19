<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfo1k5b-e.css';
import '../../css/u/u0q_e1bqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":14};
const content = `<path class="sfo1k5b-e"/><path class="u0q_e1bqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:email" {...props}></Icon>
