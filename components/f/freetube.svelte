<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b72h2zs-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b72h2zs-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:freetube" {...props}></Icon>
