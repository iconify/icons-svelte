<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncxwn206i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ncxwn206i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dumbbell-large-outline" {...props}></Icon>
