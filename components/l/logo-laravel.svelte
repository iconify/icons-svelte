<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0a1o5sny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f0a1o5sny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-laravel" {...props}></Icon>
