<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyj-90b1w.css';
import '../../css/b/b133qtshg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vyj-90b1w"/><path class="b133qtshg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:notification-unread-bold" {...props}></Icon>
