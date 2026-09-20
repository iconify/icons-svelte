<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/db0z5or4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="db0z5or4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:cloud-solid" {...props}></Icon>
