<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv5p8fbpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gv5p8fbpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:alarm-slash-filled" {...props}></Icon>
