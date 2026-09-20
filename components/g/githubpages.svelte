<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c13jq1byf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c13jq1byf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:githubpages" {...props}></Icon>
