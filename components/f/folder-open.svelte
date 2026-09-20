<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1x5f2bcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="o1x5f2bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:folder-open" {...props}></Icon>
