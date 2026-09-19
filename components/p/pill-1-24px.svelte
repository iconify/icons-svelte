<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eus48hbuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eus48hbuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:pill-1-24px" {...props}></Icon>
