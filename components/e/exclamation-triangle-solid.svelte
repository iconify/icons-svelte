<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfj4fbbbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cfj4fbbbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:exclamation-triangle-solid" {...props}></Icon>
