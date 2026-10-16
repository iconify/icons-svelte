<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alk5rr8yk.css';
import '../../css/b/bclccdbvo.css';
import '../../css/e/eveyughjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="alk5rr8yk"/><path class="bclccdbvo"/><path class="eveyughjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charging-canopy-48-bold" {...props}></Icon>
