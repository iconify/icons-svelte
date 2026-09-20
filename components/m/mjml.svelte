<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mz_6y8b0c.css';
import '../../css/n/nbgejx56b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mz_6y8b0c"/><path class="nbgejx56b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mjml" {...props}></Icon>
