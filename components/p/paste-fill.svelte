<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx6cfq3eo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nx6cfq3eo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:paste-fill" {...props}></Icon>
