<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek537ccbf.css';
import '../../css/f/fgut1gbfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ek537ccbf"/><path class="fgut1gbfe ouiIcon__fillSecondary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:app-code" {...props}></Icon>
