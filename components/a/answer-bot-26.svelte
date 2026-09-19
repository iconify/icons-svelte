<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvng27k2m.css';
import '../../css/u/utmbef4et.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<rect class="cvng27k2m"/><rect class="utmbef4et"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:answer-bot-26" {...props}></Icon>
