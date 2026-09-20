<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af786g-gs.css';
import '../../css/t/tf51z5b-b.css';
import '../../css/e/e5y3liomb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="af786g-gs"/><path class="tf51z5b-b"/><path class="e5y3liomb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:rgen" {...props}></Icon>
