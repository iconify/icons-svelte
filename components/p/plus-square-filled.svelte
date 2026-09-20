<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ociw6s2sq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ociw6s2sq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:plus-square-filled" {...props}></Icon>
