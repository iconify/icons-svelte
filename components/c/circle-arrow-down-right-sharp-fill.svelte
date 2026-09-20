<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpl7iyi0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lpl7iyi0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-arrow-down-right-sharp-fill" {...props}></Icon>
