<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb0i8bcuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kb0i8bcuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:pencil" {...props}></Icon>
