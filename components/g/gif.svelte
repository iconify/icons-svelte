<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi9pucb8a.css';
import '../../css/s/s08qpzh5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fi9pucb8a"/><path clip-rule="evenodd" class="s08qpzh5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:gif" {...props}></Icon>
