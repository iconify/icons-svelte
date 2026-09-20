<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns121jb1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ns121jb1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-top-sharp" {...props}></Icon>
