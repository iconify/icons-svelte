<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl2db7o2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tl2db7o2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:email-forward-filled" {...props}></Icon>
