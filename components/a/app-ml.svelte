<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e64vo7e9t.css';
import '../../css/i/iste4e9kh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e64vo7e9t ouiIcon__fillSecondary"/><path class="iste4e9kh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:app-ml" {...props}></Icon>
