<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7ajt9kvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z7ajt9kvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:assemblyscript" {...props}></Icon>
