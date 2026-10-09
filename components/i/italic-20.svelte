<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjqwoqbfe.css';
import '../../css/f/fxdh-t-8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pjqwoqbfe"/><path class="fxdh-t-8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:italic-20" {...props}></Icon>
