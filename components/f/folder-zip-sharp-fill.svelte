<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0szax6bu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w0szax6bu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:folder-zip-sharp-fill" {...props}></Icon>
