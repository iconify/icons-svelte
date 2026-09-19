<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruobg3brx.css';
import '../../css/n/nr8lbkbxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ruobg3brx"/><path class="nr8lbkbxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:folder-lock-solid" {...props}></Icon>
