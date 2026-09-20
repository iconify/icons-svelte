<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6nvqp9jz.css';
import '../../css/t/tynapsbmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u6nvqp9jz"/><path class="tynapsbmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:envelope-flying-light" {...props}></Icon>
