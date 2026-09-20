<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q49_fbchc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5.5,"top":-2};
const content = `<path class="q49_fbchc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:building-f" {...props}></Icon>
