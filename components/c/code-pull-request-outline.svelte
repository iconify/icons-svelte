<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp8skrysh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bp8skrysh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:code-pull-request-outline" {...props}></Icon>
