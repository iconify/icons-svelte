<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqtw05bit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yqtw05bit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:edit-unmask" {...props}></Icon>
