<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gumwfk82y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gumwfk82y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:go" {...props}></Icon>
