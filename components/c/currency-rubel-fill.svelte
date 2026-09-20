<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5_-fllxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5_-fllxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-rubel-fill" {...props}></Icon>
