<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihyzhxboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ihyzhxboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:calendar-exclamation-solid" {...props}></Icon>
