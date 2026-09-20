<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apldvfbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="apldvfbhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:credit-card-plus-sharp" {...props}></Icon>
