<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4drh5_en.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r4drh5_en"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gitbook" {...props}></Icon>
