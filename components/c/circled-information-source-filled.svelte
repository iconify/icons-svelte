<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk5j4gb-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="bk5j4gb-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:circled-information-source-filled" {...props}></Icon>
