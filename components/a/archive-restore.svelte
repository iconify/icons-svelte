<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8ftxq4wx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j8ftxq4wx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:archive-restore" {...props}></Icon>
