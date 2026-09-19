<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rf3at3bvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rf3at3bvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:folder-plus-solid" {...props}></Icon>
