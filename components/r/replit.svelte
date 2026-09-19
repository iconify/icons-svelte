<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9jc9z6kw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="b9jc9z6kw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:replit" {...props}></Icon>
