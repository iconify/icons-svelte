<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_jkadc9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u_jkadc9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:closed-captions-tag-solid" {...props}></Icon>
