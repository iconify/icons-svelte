<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bu4ip1kvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bu4ip1kvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:logo-telegram" {...props}></Icon>
