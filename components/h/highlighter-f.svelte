<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2lcz1btz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-1,"top":-1.5};
const content = `<path class="q2lcz1btz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:highlighter-f" {...props}></Icon>
