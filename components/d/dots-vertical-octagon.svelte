<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbwppomqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbwppomqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:dots-vertical-octagon" {...props}></Icon>
