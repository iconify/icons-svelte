<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqdd3lnje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hqdd3lnje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:penpot" {...props}></Icon>
