<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egibrybys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="egibrybys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:paper-plane" {...props}></Icon>
