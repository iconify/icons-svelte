<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqmwze80o.css';
import '../../css/e/e3mo12bkj.css';
import '../../css/n/n8-5n64ef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cqmwze80o"/><path class="e3mo12bkj"/><path class="n8-5n64ef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-alert-48" {...props}></Icon>
