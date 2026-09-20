<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4vb3mbqk.css';
import '../../css/o/ol95ujbyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u4vb3mbqk"/><path class="ol95ujbyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:inj" {...props}></Icon>
