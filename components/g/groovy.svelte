<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g64400p-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g64400p-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:groovy" {...props}></Icon>
