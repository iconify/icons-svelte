<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klsefs8bw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="klsefs8bw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:phone-plus" {...props}></Icon>
