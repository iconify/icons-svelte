<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpx5-6bdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpx5-6bdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:people-filled" {...props}></Icon>
