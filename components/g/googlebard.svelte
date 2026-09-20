<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/en5m6dbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="en5m6dbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:googlebard" {...props}></Icon>
