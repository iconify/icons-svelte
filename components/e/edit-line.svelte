<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvk1-n9_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gvk1-n9_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:edit-line" {...props}></Icon>
