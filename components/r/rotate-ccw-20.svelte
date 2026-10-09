<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8vhyqvci.css';
import '../../css/f/f8cnuqbvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t8vhyqvci"/><path class="f8cnuqbvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rotate-ccw-20" {...props}></Icon>
