<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/soo8zp4nw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="soo8zp4nw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:affinity" {...props}></Icon>
