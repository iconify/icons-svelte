<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvxjswbzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mvxjswbzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:clock-fill" {...props}></Icon>
