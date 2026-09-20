<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e61n9-bdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e61n9-bdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:openjdk" {...props}></Icon>
