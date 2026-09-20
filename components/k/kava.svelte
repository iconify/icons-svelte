<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wx6v9et_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wx6v9et_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:kava" {...props}></Icon>
