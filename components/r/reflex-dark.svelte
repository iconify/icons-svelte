<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kw3edznub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":12};
const content = `<path class="kw3edznub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:reflex-dark" {...props}></Icon>
