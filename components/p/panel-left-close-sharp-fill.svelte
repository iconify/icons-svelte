<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q14syjb8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q14syjb8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-left-close-sharp-fill" {...props}></Icon>
