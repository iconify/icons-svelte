<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7qvhrbja.css';
import '../../css/q/q-q0i_h1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v7qvhrbja"/><path class="q-q0i_h1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:copy-clipboard" {...props}></Icon>
