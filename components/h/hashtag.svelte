<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq-ydmtln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gq-ydmtln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:hashtag" {...props}></Icon>
