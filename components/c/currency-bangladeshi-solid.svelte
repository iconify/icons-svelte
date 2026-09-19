<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0zq4nbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e0zq4nbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:currency-bangladeshi-solid" {...props}></Icon>
