<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6xgii.css';
import '../../css/s/so-from-54.css';
import '../../css/f/fill-to-1.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q6xgii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:filter-filled" {...props}></Icon>
