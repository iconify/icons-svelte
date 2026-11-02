<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2i44_bqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h2i44_bqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:banknote-arrow-down-fill" {...props}></Icon>
