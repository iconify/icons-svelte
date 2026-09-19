<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0wu_68ee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="x0wu_68ee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:guidedog" {...props}></Icon>
