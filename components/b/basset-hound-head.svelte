<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6fooktbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n6fooktbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:basset-hound-head" {...props}></Icon>
