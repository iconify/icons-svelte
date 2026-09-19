<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs3y2sk5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qs3y2sk5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:address-book-filled" {...props}></Icon>
