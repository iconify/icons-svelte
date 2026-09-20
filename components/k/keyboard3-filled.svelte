<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lepxpsibw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lepxpsibw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:keyboard3-filled" {...props}></Icon>
