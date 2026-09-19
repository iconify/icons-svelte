<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d08ecwr6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="d08ecwr6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:mariadb" {...props}></Icon>
