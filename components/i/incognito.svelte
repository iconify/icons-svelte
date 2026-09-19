<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_vmbnb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w_vmbnb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:incognito" {...props}></Icon>
