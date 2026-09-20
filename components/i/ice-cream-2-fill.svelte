<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5oj8v8lj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o5oj8v8lj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ice-cream-2-fill" {...props}></Icon>
