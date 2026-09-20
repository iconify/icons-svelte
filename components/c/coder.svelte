<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idxmc4bac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="idxmc4bac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:coder" {...props}></Icon>
