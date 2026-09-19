<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8tt_bjdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f8tt_bjdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pot-02" {...props}></Icon>
