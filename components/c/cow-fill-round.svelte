<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i461mdo7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i461mdo7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cow-fill-round" {...props}></Icon>
