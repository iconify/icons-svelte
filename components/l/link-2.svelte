<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnuezh7xd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mnuezh7xd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:link-2" {...props}></Icon>
