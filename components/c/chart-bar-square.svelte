<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-7mvzbzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q-7mvzbzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chart-bar-square" {...props}></Icon>
