<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er5-kobdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="er5-kobdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:delta" {...props}></Icon>
