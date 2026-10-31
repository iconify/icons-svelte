<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7h-p1bgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y7h-p1bgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:percent-solid" {...props}></Icon>
