<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo0whm7za.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-1};
const content = `<path class="jo0whm7za"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:birthday-cake" {...props}></Icon>
