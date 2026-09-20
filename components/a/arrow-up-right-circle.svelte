<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxx8dpbmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxx8dpbmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-up-right-circle" {...props}></Icon>
