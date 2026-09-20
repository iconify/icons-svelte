<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e42y3r43j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e42y3r43j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:mainwp" {...props}></Icon>
