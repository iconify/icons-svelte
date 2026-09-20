<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqsdsgzhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zqsdsgzhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:article" {...props}></Icon>
