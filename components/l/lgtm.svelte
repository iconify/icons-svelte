<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckuicm7cn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ckuicm7cn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:lgtm" {...props}></Icon>
