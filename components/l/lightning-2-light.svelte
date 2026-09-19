<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1417k-va.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k1417k-va"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:lightning-2-light" {...props}></Icon>
