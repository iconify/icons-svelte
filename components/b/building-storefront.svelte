<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izdca7blm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="izdca7blm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:building-storefront" {...props}></Icon>
