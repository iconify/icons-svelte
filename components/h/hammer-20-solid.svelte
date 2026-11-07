<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpb5enzud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="mpb5enzud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:hammer-20-solid" {...props}></Icon>
