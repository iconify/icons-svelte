<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef38vvb1i.css';
import '../../css/b/bic9zqbfw.css';
import '../../css/u/ufp1mnb9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ef38vvb1i"/><path class="bic9zqbfw"/><path class="ufp1mnb9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:check-valve-20-bold" {...props}></Icon>
