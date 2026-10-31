<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0ih3db_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0ih3db_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bell-gloss" {...props}></Icon>
