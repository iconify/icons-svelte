<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrdvnvboj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nrdvnvboj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:caret-left-square" {...props}></Icon>
