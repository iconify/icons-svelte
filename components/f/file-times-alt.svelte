<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/baw3hgbjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="baw3hgbjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:file-times-alt" {...props}></Icon>
