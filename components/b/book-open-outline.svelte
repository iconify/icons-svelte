<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvep-8bqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gvep-8bqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:book-open-outline" {...props}></Icon>
