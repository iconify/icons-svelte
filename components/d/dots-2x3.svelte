<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_zvwqk6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_zvwqk6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:dots-2x3" {...props}></Icon>
