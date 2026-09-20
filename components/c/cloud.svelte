<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx9bkhb4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tx9bkhb4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:cloud" {...props}></Icon>
