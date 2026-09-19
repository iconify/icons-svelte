<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5i1aouls.css';
import '../../css/f/fktweubsh.css';
import '../../css/e/e39ud6bwf.css';
import '../../css/s/svdy80z7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="l5i1aouls"/><circle class="fktweubsh"/><circle class="e39ud6bwf"/><path class="svdy80z7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:pending" {...props}></Icon>
