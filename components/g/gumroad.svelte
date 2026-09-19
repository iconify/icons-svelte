<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy-mau2gx.css';
import '../../css/h/huruoib_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b gy-mau2gx"/><path class="b huruoib_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:gumroad" {...props}></Icon>
