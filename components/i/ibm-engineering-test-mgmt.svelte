<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjlrjeixl.css';
import '../../css/m/m1mt6od4j.css';
import '../../css/p/p_qb8obhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vjlrjeixl"/><path class="m1mt6od4j"/><path class="p_qb8obhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-engineering-test-mgmt" {...props}></Icon>
