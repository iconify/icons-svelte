<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af4sfbb6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="af4sfbb6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:corner-down-right-light" {...props}></Icon>
