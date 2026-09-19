<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt6gxp18b.css';
import '../../css/u/u5p0aybko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="wt6gxp18b"/><path class="u5p0aybko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:grails" {...props}></Icon>
