<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt-3h5doh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lt-3h5doh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:blood-bag-24px" {...props}></Icon>
