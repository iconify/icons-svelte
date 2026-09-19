<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9bscjvji.css';
import '../../css/y/ytxdcn94k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y9bscjvji"/><path class="ytxdcn94k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:image-alt" {...props}></Icon>
