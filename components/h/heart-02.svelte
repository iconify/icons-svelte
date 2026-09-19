<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4dxw5t5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d4dxw5t5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:heart-02" {...props}></Icon>
