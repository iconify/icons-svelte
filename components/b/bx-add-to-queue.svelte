<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eoy6vkbrs.css';
import '../../css/l/lbf20db5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eoy6vkbrs"/><path class="lbf20db5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-add-to-queue" {...props}></Icon>
