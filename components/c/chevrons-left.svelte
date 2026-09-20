<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2vzr5v5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4.5,"top":-5};
const content = `<path class="m2vzr5v5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:chevrons-left" {...props}></Icon>
