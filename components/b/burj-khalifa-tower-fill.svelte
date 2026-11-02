<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2p1vc5cp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2p1vc5cp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:burj-khalifa-tower-fill" {...props}></Icon>
