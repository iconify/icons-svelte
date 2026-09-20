<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eavl5i9ul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eavl5i9ul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hours-12" {...props}></Icon>
