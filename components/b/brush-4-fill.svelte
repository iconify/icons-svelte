<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo93vsiye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xo93vsiye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:brush-4-fill" {...props}></Icon>
