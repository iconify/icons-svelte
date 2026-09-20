<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in6jc3bsu.css';
import '../../css/z/z46kgibda.css';
import '../../css/p/p4x9h9btd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="in6jc3bsu"/><path class="z46kgibda"/><path class="p4x9h9btd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:agrs" {...props}></Icon>
