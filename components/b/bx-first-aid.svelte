<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/damh3ebto.css';
import '../../css/h/hxxd9_b1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="damh3ebto"/><path class="hxxd9_b1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-first-aid" {...props}></Icon>
