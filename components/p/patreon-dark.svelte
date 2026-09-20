<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etba4kbfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":40};
const content = `<path class="etba4kbfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:patreon-dark" {...props}></Icon>
