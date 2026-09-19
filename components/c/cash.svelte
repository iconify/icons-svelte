<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jea2sgbeu.css';
import '../../css/t/ty_ptacek.css';
import '../../css/a/ac_65uciq.css';
import '../../css/k/k5t0n_cta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jea2sgbeu"/><path class="ty_ptacek"/><circle class="ac_65uciq"/><path class="k5t0n_cta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:cash" {...props}></Icon>
