<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/po7dnf-xe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="po7dnf-xe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:currency-euro" {...props}></Icon>
