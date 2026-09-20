<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytt809b0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ytt809b0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:edit" {...props}></Icon>
