<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqx0cbb0u.css';
import '../../css/q/qrs5x0bhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="iqx0cbb0u"/><path class="qrs5x0bhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:clickhouse" {...props}></Icon>
