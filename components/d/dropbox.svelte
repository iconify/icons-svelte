<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjsl_rbqf.css';
import '../../css/a/aypvy6buw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gjsl_rbqf"/><path class="aypvy6buw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:dropbox" {...props}></Icon>
