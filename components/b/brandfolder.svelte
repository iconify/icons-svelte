<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxc81zbqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xxc81zbqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:brandfolder" {...props}></Icon>
