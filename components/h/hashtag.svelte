<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2icc0b3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w2icc0b3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:hashtag" {...props}></Icon>
