<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l44anh1gu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l44anh1gu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:music" {...props}></Icon>
