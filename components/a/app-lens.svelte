<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttck2cbln.css';
import '../../css/g/gd-53hb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ouiIcon__fillSecondary ttck2cbln"/><path class="gd-53hb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:app-lens" {...props}></Icon>
