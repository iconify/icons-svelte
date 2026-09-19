<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fepn_rb5k.css';
import '../../css/n/nq5_ejy6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="fepn_rb5k"/><path class="nq5_ejy6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:card-view-filled" {...props}></Icon>
