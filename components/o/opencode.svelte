<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwo46jzka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zwo46jzka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:opencode" {...props}></Icon>
