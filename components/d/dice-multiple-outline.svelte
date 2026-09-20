<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqkr3kbib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gqkr3kbib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:dice-multiple-outline" {...props}></Icon>
