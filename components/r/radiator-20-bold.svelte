<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqc5wb6qw.css';
import '../../css/s/s4umu5bdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mqc5wb6qw"/><path class="s4umu5bdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:radiator-20-bold" {...props}></Icon>
