<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjel4zbty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yjel4zbty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:bookmark" {...props}></Icon>
