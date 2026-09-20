<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4ciipbpv.css';
import '../../css/j/jsm8ux5rh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4ciipbpv"/><path class="jsm8ux5rh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:headphones-duotone" {...props}></Icon>
