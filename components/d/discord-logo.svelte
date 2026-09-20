<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wanl34gha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wanl34gha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:discord-logo" {...props}></Icon>
