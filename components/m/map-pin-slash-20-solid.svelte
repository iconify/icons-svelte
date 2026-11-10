<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_vtsxbao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="v_vtsxbao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:map-pin-slash-20-solid" {...props}></Icon>
