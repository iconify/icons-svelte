<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8hdzzb1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f8hdzzb1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:folder-sharp-fill" {...props}></Icon>
