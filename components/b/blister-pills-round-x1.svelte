<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myb6k18tj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="myb6k18tj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:blister-pills-round-x1" {...props}></Icon>
