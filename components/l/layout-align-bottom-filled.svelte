<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krqngr2hk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="krqngr2hk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:layout-align-bottom-filled" {...props}></Icon>
