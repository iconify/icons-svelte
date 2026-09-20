<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2mopvp0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k2mopvp0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:folder-star" {...props}></Icon>
