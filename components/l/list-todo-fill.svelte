<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2pbjb56g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q2pbjb56g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:list-todo-fill" {...props}></Icon>
