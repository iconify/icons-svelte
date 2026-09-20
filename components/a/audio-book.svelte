<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlu6r6v-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nlu6r6v-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:audio-book" {...props}></Icon>
