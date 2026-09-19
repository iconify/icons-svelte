<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhh5x7blm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rhh5x7blm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:phone-forward" {...props}></Icon>
