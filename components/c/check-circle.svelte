<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgq1o5bup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sgq1o5bup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:check-circle" {...props}></Icon>
