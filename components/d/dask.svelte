<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmjd6gzzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qmjd6gzzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:dask" {...props}></Icon>
