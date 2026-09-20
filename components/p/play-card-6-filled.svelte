<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih-nfnbzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ih-nfnbzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:play-card-6-filled" {...props}></Icon>
