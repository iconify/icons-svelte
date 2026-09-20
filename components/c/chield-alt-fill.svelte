<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ju7eqfb3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ju7eqfb3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:chield-alt-fill" {...props}></Icon>
