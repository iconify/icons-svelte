<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sel7y4boo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sel7y4boo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:pilcrow" {...props}></Icon>
