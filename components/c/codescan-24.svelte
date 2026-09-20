<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3wi9ouxj.css';
import '../../css/y/ykjnrse8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3wi9ouxj"/><path class="ykjnrse8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:codescan-24" {...props}></Icon>
