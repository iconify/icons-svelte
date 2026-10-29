<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0d-cmbof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0d-cmbof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:book-open-solid" {...props}></Icon>
