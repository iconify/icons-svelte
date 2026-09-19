<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zndtekn6f.css';
import '../../css/c/c1_dnpbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zndtekn6f"/><path class="c1_dnpbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:devpost" {...props}></Icon>
