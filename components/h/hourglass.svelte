<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqm-b-osx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqm-b-osx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:hourglass" {...props}></Icon>
