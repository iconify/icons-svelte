<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ian57fbze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ian57fbze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:coding-apps-website-web-dev-api-cloud" {...props}></Icon>
