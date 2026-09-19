<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-7oihfec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="o-7oihfec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:currency-pound" {...props}></Icon>
