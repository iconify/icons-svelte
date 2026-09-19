<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol_w2hbhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ol_w2hbhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:male-24px" {...props}></Icon>
