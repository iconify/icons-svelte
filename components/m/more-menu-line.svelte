<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or_6jdb6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="or_6jdb6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:more-menu-line" {...props}></Icon>
