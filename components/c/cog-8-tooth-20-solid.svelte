<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqrfbbbyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="mqrfbbbyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:cog-8-tooth-20-solid" {...props}></Icon>
