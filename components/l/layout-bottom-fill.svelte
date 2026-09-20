<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btp-w9hcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="btp-w9hcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-bottom-fill" {...props}></Icon>
