<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/geqe3__ht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="geqe3__ht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:mahindra" {...props}></Icon>
