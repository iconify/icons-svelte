<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifwvrxeft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ifwvrxeft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:ellipsis-v" {...props}></Icon>
