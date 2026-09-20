<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt6741bkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lt6741bkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:mailbox-off" {...props}></Icon>
