<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja-mhib-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ja-mhib-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:extension-us" {...props}></Icon>
