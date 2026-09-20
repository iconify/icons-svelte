<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efkzp1eud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="efkzp1eud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:hairdryer" {...props}></Icon>
