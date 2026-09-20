<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7g8utbwr.css';
import '../../css/v/v8v4y7b1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o7g8utbwr"/><path class="v8v4y7b1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:eye-2-line" {...props}></Icon>
