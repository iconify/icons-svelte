<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/et_p5ualv.css';
import '../../css/r/rudk2pbyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="et_p5ualv"/><path class="rudk2pbyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:person-key-fill-20" {...props}></Icon>
