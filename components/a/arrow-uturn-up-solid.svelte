<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj-z-xb9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uj-z-xb9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-uturn-up-solid" {...props}></Icon>
