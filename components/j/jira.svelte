<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsvu0-b5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="tsvu0-b5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:jira" {...props}></Icon>
