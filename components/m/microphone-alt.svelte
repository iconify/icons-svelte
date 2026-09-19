<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzxa7rbby.css';
import '../../css/j/jfmxxebmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzxa7rbby"/><path class="jfmxxebmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:microphone-alt" {...props}></Icon>
