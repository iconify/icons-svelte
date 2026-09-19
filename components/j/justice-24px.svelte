<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-oqsxcbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a-oqsxcbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:justice-24px" {...props}></Icon>
