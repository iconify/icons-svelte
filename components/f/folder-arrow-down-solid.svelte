<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aa6-rdobn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aa6-rdobn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:folder-arrow-down-solid" {...props}></Icon>
