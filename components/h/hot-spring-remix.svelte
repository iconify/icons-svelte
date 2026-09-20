<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srgcg9p3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="srgcg9p3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:hot-spring-remix" {...props}></Icon>
