<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xiwjijb7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xiwjijb7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bracket-arrow-left-fill" {...props}></Icon>
