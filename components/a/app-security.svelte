<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j54z2ny8a.css';
import '../../css/o/og107ss5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j54z2ny8a"/><path class="og107ss5y ouiIcon__fillSecondary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:app-security" {...props}></Icon>
