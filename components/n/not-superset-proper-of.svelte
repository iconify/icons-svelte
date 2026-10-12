<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npr62rbrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="npr62rbrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:not-superset-proper-of" {...props}></Icon>
