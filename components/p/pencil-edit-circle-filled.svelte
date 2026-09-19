<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdtpq1bge.css';
import '../../css/l/l2x5o3qgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mdtpq1bge"/><path class="l2x5o3qgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pencil-edit-circle-filled" {...props}></Icon>
