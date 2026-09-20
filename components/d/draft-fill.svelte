<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz5jbmvpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zz5jbmvpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:draft-fill" {...props}></Icon>
