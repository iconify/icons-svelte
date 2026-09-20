<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jie5d7b6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jie5d7b6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:choice-fill" {...props}></Icon>
