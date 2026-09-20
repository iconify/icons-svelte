<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzh2qt3br.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qzh2qt3br"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:menu" {...props}></Icon>
