<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plw3qfx0k.css';
import '../../css/i/i7sr6ubzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="plw3qfx0k"/><path class="i7sr6ubzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:numbered-list-solid" {...props}></Icon>
