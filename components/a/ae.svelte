<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9gujfbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9gujfbhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ae" {...props}></Icon>
