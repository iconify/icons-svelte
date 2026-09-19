<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7-7_jn-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n7-7_jn-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:medical-flask" {...props}></Icon>
