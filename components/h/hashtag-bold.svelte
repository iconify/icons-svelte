<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uiaujwb6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uiaujwb6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hashtag-bold" {...props}></Icon>
