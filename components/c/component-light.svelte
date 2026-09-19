<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6t2jv6zz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k6t2jv6zz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:component-light" {...props}></Icon>
