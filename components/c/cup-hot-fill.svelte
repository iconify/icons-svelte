<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj3p56bdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bj3p56bdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:cup-hot-fill" {...props}></Icon>
