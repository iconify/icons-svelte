<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxj3gjb5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxj3gjb5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:netim" {...props}></Icon>
