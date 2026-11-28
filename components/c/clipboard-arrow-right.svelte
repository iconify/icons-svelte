<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcx7yod2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kcx7yod2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:clipboard-arrow-right" {...props}></Icon>
