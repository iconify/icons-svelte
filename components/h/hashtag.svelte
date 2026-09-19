<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sed2vvolb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sed2vvolb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:hashtag" {...props}></Icon>
