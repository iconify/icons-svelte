<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynen73b7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ynen73b7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:direction-line" {...props}></Icon>
