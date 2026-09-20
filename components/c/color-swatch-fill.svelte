<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjc3tibnp.css';
import '../../css/d/dacej6b-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xjc3tibnp"/><path class="dacej6b-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:color-swatch-fill" {...props}></Icon>
