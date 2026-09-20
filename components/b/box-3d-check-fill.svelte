<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt59svwig.css';
import '../../css/d/d5bwuacpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kt59svwig"/><path class="d5bwuacpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:box-3d-check-fill" {...props}></Icon>
