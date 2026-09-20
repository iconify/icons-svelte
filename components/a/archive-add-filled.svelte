<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-y5yjkuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-y5yjkuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:archive-add-filled" {...props}></Icon>
