<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja00h22ea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ja00h22ea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:bookmark-alt" {...props}></Icon>
