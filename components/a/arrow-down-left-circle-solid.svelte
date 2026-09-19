<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhyma36tc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bhyma36tc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:arrow-down-left-circle-solid" {...props}></Icon>
