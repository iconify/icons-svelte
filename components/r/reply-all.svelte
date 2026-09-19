<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6ayae2vq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f6ayae2vq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:reply-all" {...props}></Icon>
