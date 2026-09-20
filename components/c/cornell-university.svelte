<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv0et_yeu.css';
import '../../css/g/gfzaxkurt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":129.378};
const content = `<path class="sv0et_yeu"/><path class="gfzaxkurt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cornell-university" {...props}></Icon>
