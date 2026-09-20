<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0tyl5b3k.css';
import '../../css/f/fs0iosbnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u0tyl5b3k"/><path class="fs0iosbnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:oddz" {...props}></Icon>
