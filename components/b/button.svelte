<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzc1k193u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qzc1k193u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:button" {...props}></Icon>
