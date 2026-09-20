<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpf5-09ok.css';
import '../../css/h/hpmvmqb-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":25};
const content = `<path class="wpf5-09ok"/><path class="hpmvmqb-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:ai-search-filled" {...props}></Icon>
