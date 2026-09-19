<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cty9l0r9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cty9l0r9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:mysa-thermostat" {...props}></Icon>
