<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8z9yx54k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s8z9yx54k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:chanel" {...props}></Icon>
