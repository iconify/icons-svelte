<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oblc-wbem.css';
import '../../css/f/f5bqv3-2b.css';
import '../../css/z/z4sj3ixdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oblc-wbem"/><path class="f5bqv3-2b"/><path class="z4sj3ixdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pets-allowed-48" {...props}></Icon>
