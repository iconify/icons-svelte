<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2e3_cb_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2e3_cb_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:faker" {...props}></Icon>
