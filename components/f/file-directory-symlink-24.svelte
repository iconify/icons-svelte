<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auljhabfb.css';
import '../../css/z/zqdkcibks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="auljhabfb"/><path class="zqdkcibks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:file-directory-symlink-24" {...props}></Icon>
