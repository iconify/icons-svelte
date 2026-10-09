<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aoae257bl.css';
import '../../css/g/gi5oa8bic.css';
import '../../css/h/hcflecbqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="aoae257bl"/><path class="gi5oa8bic"/><path class="hcflecbqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:penstock-48" {...props}></Icon>
