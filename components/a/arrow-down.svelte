<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsoh_ofzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="zsoh_ofzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:arrow-down" {...props}></Icon>
