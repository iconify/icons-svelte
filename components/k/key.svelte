<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggvbkqb-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ggvbkqb-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:key" {...props}></Icon>
