<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iikr6dbva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iikr6dbva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:mailbox-full" {...props}></Icon>
