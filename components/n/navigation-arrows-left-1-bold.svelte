<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arlrzbbsj.css';
import '../../css/r/rkc5kdsmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="arlrzbbsj"/><path class="rkc5kdsmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:navigation-arrows-left-1-bold" {...props}></Icon>
