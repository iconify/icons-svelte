<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n90uq3bfu.css';
import '../../css/j/jyzdacbcc.css';
import '../../css/b/b9-qakbjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n90uq3bfu"/><path class="jyzdacbcc ouiIcon__fillSecondary"/><path class="b9-qakbjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:app-metricbeat" {...props}></Icon>
