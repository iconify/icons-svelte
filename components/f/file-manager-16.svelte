<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-e4ckbto.css';
import '../../css/b/birgbmbwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="u-e4ckbto"/><path clip-rule="evenodd" class="birgbmbwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:file-manager-16" {...props}></Icon>
