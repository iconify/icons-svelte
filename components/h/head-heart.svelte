<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-v8w7bie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-v8w7bie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:head-heart" {...props}></Icon>
