<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s46uwy_pw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="s46uwy_pw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:css3-solid" {...props}></Icon>
