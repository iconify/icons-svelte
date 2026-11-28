<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk7mgkuxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bk7mgkuxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:axe" {...props}></Icon>
