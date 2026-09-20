<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/go_38giyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="go_38giyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-2-outline" {...props}></Icon>
