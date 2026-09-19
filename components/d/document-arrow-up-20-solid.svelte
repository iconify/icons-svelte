<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m18kcqbpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="m18kcqbpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:document-arrow-up-20-solid" {...props}></Icon>
