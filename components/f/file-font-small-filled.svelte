<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezuxa926a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ezuxa926a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:file-font-small-filled" {...props}></Icon>
