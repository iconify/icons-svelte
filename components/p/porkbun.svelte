<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvs3i2z5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gvs3i2z5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:porkbun" {...props}></Icon>
