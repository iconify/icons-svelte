<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/keu35jbsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="keu35jbsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:currency-euro" {...props}></Icon>
