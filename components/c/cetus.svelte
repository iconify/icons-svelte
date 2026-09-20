<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3jdj3btd.css';
import '../../css/t/t61q91bzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w3jdj3btd"/><path class="t61q91bzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cetus" {...props}></Icon>
