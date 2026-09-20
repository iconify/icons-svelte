<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/moxt6ocnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="moxt6ocnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:moon" {...props}></Icon>
