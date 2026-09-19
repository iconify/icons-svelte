<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2kv7-_oa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n2kv7-_oa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:kickstarter" {...props}></Icon>
