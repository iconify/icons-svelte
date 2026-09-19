<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxl64k79c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxl64k79c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:email-open-alt" {...props}></Icon>
