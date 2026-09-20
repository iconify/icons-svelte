<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b80ez7bji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b80ez7bji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:reptile" {...props}></Icon>
