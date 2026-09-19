<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/beqxhtbkf.css';
import '../../css/w/wd6mpsb3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="beqxhtbkf"/><path class="wd6mpsb3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:reader-following-conversation" {...props}></Icon>
