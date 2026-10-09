<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st-nb-bnw.css';
import '../../css/t/tiq8xcncs.css';
import '../../css/i/irdsaebul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="st-nb-bnw"/><path class="tiq8xcncs"/><path class="irdsaebul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:megaphone-20" {...props}></Icon>
