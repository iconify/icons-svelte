<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6s17jbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t6s17jbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:chevron-down-small" {...props}></Icon>
