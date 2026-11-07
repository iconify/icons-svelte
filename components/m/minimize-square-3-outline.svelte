<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhh-lmb1b.css';
import '../../css/s/s1xezt9uh.css';
import '../../css/r/ru5wvccub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhh-lmb1b"/><path class="s1xezt9uh"/><path clip-rule="evenodd" class="ru5wvccub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:minimize-square-3-outline" {...props}></Icon>
