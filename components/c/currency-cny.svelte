<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/teg8udb9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="teg8udb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:currency-cny" {...props}></Icon>
