<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys83zjbjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ys83zjbjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:fast-forward-back-fill" {...props}></Icon>
