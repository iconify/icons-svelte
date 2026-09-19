<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmojuv_0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dmojuv_0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:asterisk-02" {...props}></Icon>
