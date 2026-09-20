<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8pb41bfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e8pb41bfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:angle-up" {...props}></Icon>
