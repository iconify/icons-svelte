<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itrxtc5lt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="itrxtc5lt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:fxs" {...props}></Icon>
