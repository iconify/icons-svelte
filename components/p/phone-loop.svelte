<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9uwov.css';
import '../../css/s/so-from-62.css';
import '../../css/t/tr-b5mmly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9uwov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:phone-loop" {...props}></Icon>
