<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp2h-rbja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="bp2h-rbja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:filezilla" {...props}></Icon>
