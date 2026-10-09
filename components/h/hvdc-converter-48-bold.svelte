<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkzd28t8y.css';
import '../../css/h/hbji4i9fj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bkzd28t8y"/><path class="hbji4i9fj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hvdc-converter-48-bold" {...props}></Icon>
