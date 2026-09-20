<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwmyw5b7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gwmyw5b7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:hard-drive-fill" {...props}></Icon>
