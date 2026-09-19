<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hk2ugrbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hk2ugrbdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:close-small" {...props}></Icon>
