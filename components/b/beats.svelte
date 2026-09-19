<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qy3pqcxku.css';
import '../../css/g/gy0kacpby.css';
import '../../css/q/qq36dbo-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="qy3pqcxku"/><path class="gy0kacpby"/><path class="qq36dbo-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:beats" {...props}></Icon>
