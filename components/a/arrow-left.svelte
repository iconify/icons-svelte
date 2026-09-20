<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjlzt-g3f.css';
import '../../css/t/t5c3kxbue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="gjlzt-g3f"/><path class="t5c3kxbue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:arrow-left" {...props}></Icon>
