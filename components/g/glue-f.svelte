<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aj3b-5bwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-7,"top":-1};
const content = `<path class="aj3b-5bwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:glue-f" {...props}></Icon>
