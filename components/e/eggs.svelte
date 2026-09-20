<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f510iwbup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-3.5};
const content = `<path class="f510iwbup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:eggs" {...props}></Icon>
