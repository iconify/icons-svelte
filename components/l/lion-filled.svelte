<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_wfrqadw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s_wfrqadw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:lion-filled" {...props}></Icon>
