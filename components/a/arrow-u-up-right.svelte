<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8z3sszqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8z3sszqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-u-up-right" {...props}></Icon>
