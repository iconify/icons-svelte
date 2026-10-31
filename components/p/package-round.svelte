<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zegjqgb0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zegjqgb0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:package-round" {...props}></Icon>
