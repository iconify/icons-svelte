<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1dtv5bnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c1dtv5bnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:folder-heart" {...props}></Icon>
