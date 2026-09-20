<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2yj9i4te.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f2yj9i4te"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:pipe-24" {...props}></Icon>
