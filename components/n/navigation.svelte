<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzn8lfy8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bzn8lfy8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:navigation" {...props}></Icon>
