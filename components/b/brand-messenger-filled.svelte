<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/va8ywzbbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="va8ywzbbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-messenger-filled" {...props}></Icon>
