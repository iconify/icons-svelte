<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/go-f_ehsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="go-f_ehsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:id-card-solid" {...props}></Icon>
