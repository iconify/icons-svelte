<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks9mkoovd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ks9mkoovd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:mouse" {...props}></Icon>
