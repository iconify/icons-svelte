<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdm5t7wmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tdm5t7wmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:macy-s" {...props}></Icon>
