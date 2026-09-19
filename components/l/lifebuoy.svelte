<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkihqds9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="tkihqds9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:lifebuoy" {...props}></Icon>
