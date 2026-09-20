<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9utltikj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t9utltikj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:jaguar" {...props}></Icon>
