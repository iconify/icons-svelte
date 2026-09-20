<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9oho0b1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="x9oho0b1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:alipay" {...props}></Icon>
