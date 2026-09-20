<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggbg5jbso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ggbg5jbso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:anthropic" {...props}></Icon>
