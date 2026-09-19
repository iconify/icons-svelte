<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a58u95buk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="a58u95buk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:azuresqldatabase" {...props}></Icon>
