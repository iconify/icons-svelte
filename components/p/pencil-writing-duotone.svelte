<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1cyrmb8e.css';
import '../../css/m/mvssxhbia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1cyrmb8e"/><path class="mvssxhbia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:pencil-writing-duotone" {...props}></Icon>
