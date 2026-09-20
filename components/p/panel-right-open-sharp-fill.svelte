<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6fh3-v4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n6fh3-v4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:panel-right-open-sharp-fill" {...props}></Icon>
