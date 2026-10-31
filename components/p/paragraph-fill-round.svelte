<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcgi_3evl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tcgi_3evl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:paragraph-fill-round" {...props}></Icon>
