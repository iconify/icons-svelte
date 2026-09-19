<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4v32jb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="v4v32jb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:pulumi-wordmark" {...props}></Icon>
