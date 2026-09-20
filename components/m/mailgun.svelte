<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up92zwb6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="up92zwb6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:mailgun" {...props}></Icon>
