<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei2jpv_jy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ei2jpv_jy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:knowledgebase" {...props}></Icon>
