<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3v6f1bdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k3v6f1bdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:folder-remove-filled" {...props}></Icon>
