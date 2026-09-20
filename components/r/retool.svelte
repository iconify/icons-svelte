<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef-fu9bpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ef-fu9bpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:retool" {...props}></Icon>
