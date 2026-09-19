<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3qq0hx9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="v3qq0hx9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:chakraui" {...props}></Icon>
