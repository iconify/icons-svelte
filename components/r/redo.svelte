<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjinq55nx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xjinq55nx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:redo" {...props}></Icon>
