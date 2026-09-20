<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-fojub-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-fojub-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:paperclip-24" {...props}></Icon>
