<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uws-23bsl.css';
import '../../css/d/d83mplq2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uws-23bsl"/><path class="d83mplq2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:credit-card-16" {...props}></Icon>
