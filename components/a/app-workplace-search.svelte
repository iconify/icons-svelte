<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n28sx5w0p.css';
import '../../css/h/h81cxxbry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n28sx5w0p"/><path class="h81cxxbry ouiIcon__fillSecondary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:app-workplace-search" {...props}></Icon>
