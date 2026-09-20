<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phcz05bgu.css';
import '../../css/a/a4-kayjwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="phcz05bgu"/><path class="a4-kayjwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:car-repair-engine-bold" {...props}></Icon>
