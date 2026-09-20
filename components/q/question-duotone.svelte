<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vla37tbfm.css';
import '../../css/t/t576d3m0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vla37tbfm"/><path class="t576d3m0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:question-duotone" {...props}></Icon>
