<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7qcaq70w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l7qcaq70w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:forbid-2-filled" {...props}></Icon>
