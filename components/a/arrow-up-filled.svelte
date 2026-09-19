<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0bk5fh_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x0bk5fh_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-up-filled" {...props}></Icon>
