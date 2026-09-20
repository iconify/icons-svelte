<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9v5hwa6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p9v5hwa6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:horizontal-top-right-main" {...props}></Icon>
