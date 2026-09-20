<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0ipez3cn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b0ipez3cn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bancor" {...props}></Icon>
