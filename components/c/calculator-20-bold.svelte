<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp1n75bba.css';
import '../../css/o/osbs8kx0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pp1n75bba"/><path class="osbs8kx0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:calculator-20-bold" {...props}></Icon>
