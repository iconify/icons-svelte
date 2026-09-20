<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ao5ewccyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ao5ewccyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:burj-khalifa-tower-line" {...props}></Icon>
