<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-7g8zgze.css';
import '../../css/c/ca_dbzwra.css';
import '../../css/e/evhwq2bos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c-7g8zgze"/><path class="ca_dbzwra"/><path class="evhwq2bos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lasso-48" {...props}></Icon>
