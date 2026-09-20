<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omh5kl7yl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="omh5kl7yl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:media-quaver-active" {...props}></Icon>
