<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlv67-bal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wlv67-bal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:handset" {...props}></Icon>
