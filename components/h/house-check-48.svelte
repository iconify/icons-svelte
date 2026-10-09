<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqmwze80o.css';
import '../../css/e/e3mo12bkj.css';
import '../../css/f/f54j4-b-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cqmwze80o"/><path class="e3mo12bkj"/><path class="f54j4-b-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-check-48" {...props}></Icon>
