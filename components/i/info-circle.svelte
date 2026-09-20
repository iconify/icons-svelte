<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmderk_zc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zmderk_zc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:info-circle" {...props}></Icon>
