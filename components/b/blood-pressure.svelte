<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yok2dcbit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yok2dcbit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:blood-pressure" {...props}></Icon>
