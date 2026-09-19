<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmch1189h.css';
import '../../css/n/n_0uj0b-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="zmch1189h"/><path class="n_0uj0b-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:gallery-vertical-filled" {...props}></Icon>
