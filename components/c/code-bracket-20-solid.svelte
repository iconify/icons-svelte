<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spw5_r41r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="spw5_r41r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:code-bracket-20-solid" {...props}></Icon>
