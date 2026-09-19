<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozmn8obvd.css';
import '../../css/z/zsbatf1yf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ozmn8obvd"/><path class="zsbatf1yf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:image-no-background" {...props}></Icon>
