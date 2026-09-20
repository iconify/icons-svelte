<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am6292b6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="am6292b6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:forum" {...props}></Icon>
