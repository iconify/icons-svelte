<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd63qqbhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pd63qqbhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:face-wink" {...props}></Icon>
