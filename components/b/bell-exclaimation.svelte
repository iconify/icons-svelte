<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucyflh_rw.css';
import '../../css/h/hoos2y8tw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ucyflh_rw"/><path class="hoos2y8tw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:bell-exclaimation" {...props}></Icon>
