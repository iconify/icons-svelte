<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkrwubblf.css';
import '../../css/j/jm1k0nbux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wkrwubblf"/><path class="jm1k0nbux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:android-fill" {...props}></Icon>
