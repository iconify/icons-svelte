<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uylhht6xy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uylhht6xy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:invoice-edit" {...props}></Icon>
