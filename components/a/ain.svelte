<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q60hvuydw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q60hvuydw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ain" {...props}></Icon>
