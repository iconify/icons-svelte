<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqho9g-ds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bqho9g-ds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:corner-right-down-outline" {...props}></Icon>
