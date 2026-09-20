<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/holfdgb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="holfdgb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:radar-2-filled" {...props}></Icon>
