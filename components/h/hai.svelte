<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfw37-bnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tfw37-bnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:hai" {...props}></Icon>
