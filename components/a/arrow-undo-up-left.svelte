<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysu_7yk8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ysu_7yk8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:arrow-undo-up-left" {...props}></Icon>
