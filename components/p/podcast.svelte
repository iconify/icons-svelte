<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spa_k7f-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="spa_k7f-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:podcast" {...props}></Icon>
