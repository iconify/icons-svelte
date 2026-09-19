<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyow3oocf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="kyow3oocf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:angle-dobule-right" {...props}></Icon>
