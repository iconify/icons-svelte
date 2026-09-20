<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxxqprb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxxqprb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cardano" {...props}></Icon>
