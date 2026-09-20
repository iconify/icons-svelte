<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_osj0ijb.css';
import '../../css/h/h7n9wpcnw.css';
import '../../css/j/jb0hwxb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_osj0ijb"/><path clip-rule="evenodd" class="h7n9wpcnw"/><path clip-rule="evenodd" class="jb0hwxb_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:emoji-grin" {...props}></Icon>
