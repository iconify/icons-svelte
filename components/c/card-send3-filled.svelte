<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o58bh9b7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o58bh9b7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:card-send3-filled" {...props}></Icon>
