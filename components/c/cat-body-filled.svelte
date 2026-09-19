<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wp3tad87r.css';
import '../../css/h/hbgkxabbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wp3tad87r"/><path class="hbgkxabbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cat-body-filled" {...props}></Icon>
