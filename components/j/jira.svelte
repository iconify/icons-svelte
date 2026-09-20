<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvkrq302u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mvkrq302u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:jira" {...props}></Icon>
