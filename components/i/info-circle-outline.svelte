<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pakn2i1un.css';
import '../../css/y/yxx4r0hjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pakn2i1un"/><path clip-rule="evenodd" class="yxx4r0hjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:info-circle-outline" {...props}></Icon>
