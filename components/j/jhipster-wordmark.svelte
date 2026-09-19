<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tum2ujb2a.css';
import '../../css/t/tets5tbsv.css';
import '../../css/d/dmkkcgbra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="tum2ujb2a"/><path class="tets5tbsv"/><path class="dmkkcgbra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:jhipster-wordmark" {...props}></Icon>
