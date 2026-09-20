<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptn6lmbaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ptn6lmbaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:direction-up-right-2" {...props}></Icon>
