<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvofh2j9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-5};
const content = `<path class="uvofh2j9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:cloud" {...props}></Icon>
