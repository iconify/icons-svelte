<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtc54ubii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qtc54ubii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:kat" {...props}></Icon>
