<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k89qbfh2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k89qbfh2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:clapperboard-open-play" {...props}></Icon>
