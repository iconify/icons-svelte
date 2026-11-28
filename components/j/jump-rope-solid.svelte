<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb4wu5xei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nb4wu5xei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:jump-rope-solid" {...props}></Icon>
