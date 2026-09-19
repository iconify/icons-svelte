<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h98jf29aj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h98jf29aj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:carets-right-left-filled" {...props}></Icon>
