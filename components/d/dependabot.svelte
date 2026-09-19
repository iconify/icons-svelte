<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dah86bnyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dah86bnyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:dependabot" {...props}></Icon>
