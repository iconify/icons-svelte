<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr3umgb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pr3umgb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:minimize-square" {...props}></Icon>
