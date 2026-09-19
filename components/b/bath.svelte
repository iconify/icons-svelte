<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo0om22dm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bo0om22dm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bath" {...props}></Icon>
