<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8b8npfbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g8b8npfbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:angle-down" {...props}></Icon>
