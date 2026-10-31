<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmg9ivb1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pmg9ivb1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:banknote-fill-round" {...props}></Icon>
