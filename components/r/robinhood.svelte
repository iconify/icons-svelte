<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sesrb2qhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sesrb2qhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:robinhood" {...props}></Icon>
