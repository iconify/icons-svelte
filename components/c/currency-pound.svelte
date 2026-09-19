<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_7y3xbjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_7y3xbjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:currency-pound" {...props}></Icon>
