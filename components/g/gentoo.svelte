<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgfij9bsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="zgfij9bsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:gentoo" {...props}></Icon>
