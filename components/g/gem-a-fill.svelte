<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8bf1t8kc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j8bf1t8kc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:gem-a-fill" {...props}></Icon>
