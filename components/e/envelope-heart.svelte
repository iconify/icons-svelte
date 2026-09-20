<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-saik79v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-saik79v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:envelope-heart" {...props}></Icon>
