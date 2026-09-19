<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m96fcwz_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="m96fcwz_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:arrow-circle-down" {...props}></Icon>
