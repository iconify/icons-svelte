<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd1ch4bgm.css';
import '../../css/d/dejpxbc6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zd1ch4bgm"/><path class="dejpxbc6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:diagram-up-bold-duotone" {...props}></Icon>
