<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f298x6yqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f298x6yqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:mailbox-outline" {...props}></Icon>
