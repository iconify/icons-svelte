<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxjzbbbhp.css';
import '../../css/z/zo9umqb3f.css';
import '../../css/z/z687dobnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxjzbbbhp"/><path class="zo9umqb3f"/><path class="z687dobnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:copy" {...props}></Icon>
