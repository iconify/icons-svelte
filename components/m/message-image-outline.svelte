<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-m7ju5pd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-m7ju5pd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:message-image-outline" {...props}></Icon>
