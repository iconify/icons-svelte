<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b70-wwoww.css';
import '../../css/v/vgzbicbpw.css';
import '../../css/i/ilgbhxbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b70-wwoww"/><path class="vgzbicbpw"/><path class="ilgbhxbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-defender-light" {...props}></Icon>
