<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofzz_rb2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ofzz_rb2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:comment-quote-outline" {...props}></Icon>
