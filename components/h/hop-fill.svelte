<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/li2usrbdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="li2usrbdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hop-fill" {...props}></Icon>
