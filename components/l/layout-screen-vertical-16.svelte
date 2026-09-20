<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilxn7f33c.css';
import '../../css/e/e-qkt480u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ilxn7f33c"/><path clip-rule="evenodd" class="e-qkt480u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:layout-screen-vertical-16" {...props}></Icon>
