<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf9hg6x8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kf9hg6x8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:phone-outgoing-fill-round" {...props}></Icon>
