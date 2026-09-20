<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6eb6zbaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6eb6zbaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:chart-50-fill" {...props}></Icon>
