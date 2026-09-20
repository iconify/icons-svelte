<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfy8v3bkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dfy8v3bkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:grid-pattern" {...props}></Icon>
