<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbk12mtzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-2};
const content = `<path class="bbk12mtzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:file-f" {...props}></Icon>
