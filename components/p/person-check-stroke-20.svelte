<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqkha6bxo.css';
import '../../css/z/zplth4i-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vqkha6bxo"/><path class="zplth4i-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:person-check-stroke-20" {...props}></Icon>
